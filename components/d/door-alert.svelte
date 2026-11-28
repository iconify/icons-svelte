<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmls51bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmls51bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:door-alert" {...props}></Icon>
