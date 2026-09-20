<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg9c4xx5n.css';
import '../../css/y/y_xndqb9y.css';
import '../../css/n/n_6vc_r2y.css';
import '../../css/q/qf8a_6bcc.css';
import '../../css/a/azk25zbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg9c4xx5n"/><path class="y_xndqb9y"/><path class="n_6vc_r2y"/><path class="qf8a_6bcc"/><path class="azk25zbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:auto-light" {...props}></Icon>
