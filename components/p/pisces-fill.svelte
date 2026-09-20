<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgu141ten.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgu141ten"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pisces-fill" {...props}></Icon>
