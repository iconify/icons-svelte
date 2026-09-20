<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpc9hgrvp.css';
import '../../css/x/xyz89xbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mpc9hgrvp"/><path class="xyz89xbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-netlify-open" {...props}></Icon>
