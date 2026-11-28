<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ces413x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ces413x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:contract-search" {...props}></Icon>
