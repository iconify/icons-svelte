<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkzb6nbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkzb6nbkw primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:align-justify-duotone" {...props}></Icon>
