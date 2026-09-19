<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/catpy3b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="catpy3b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chevron-right" {...props}></Icon>
