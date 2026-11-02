<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx6e3qbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx6e3qbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-power-fill" {...props}></Icon>
