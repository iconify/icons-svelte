<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufj8p0bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufj8p0bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:baseline-shift-solid" {...props}></Icon>
