<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7_yf3hsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7_yf3hsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:common-file-horizontal-bold" {...props}></Icon>
