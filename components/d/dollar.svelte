<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0iiieihl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0iiieihl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:dollar" {...props}></Icon>
