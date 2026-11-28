<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af1ceacli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af1ceacli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-triple-down-solid" {...props}></Icon>
