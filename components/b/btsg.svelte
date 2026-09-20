<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvfz0gvjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvfz0gvjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:btsg" {...props}></Icon>
