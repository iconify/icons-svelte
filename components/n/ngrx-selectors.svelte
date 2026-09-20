<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knujnsb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="knujnsb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ngrx-selectors" {...props}></Icon>
