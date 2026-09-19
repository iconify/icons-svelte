<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrb1y4wkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrb1y4wkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-sub-right-down" {...props}></Icon>
