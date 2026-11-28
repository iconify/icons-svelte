<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojm_wssze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojm_wssze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pliers" {...props}></Icon>
