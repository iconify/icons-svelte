<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfae_b7ux.css';
import '../../css/d/dqr3ofb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lfae_b7ux"/><circle class="dqr3ofb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:d" {...props}></Icon>
