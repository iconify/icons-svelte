<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp7k9_mku.css';
import '../../css/b/btu4zi_dc.css';
import '../../css/x/xcbtxr5ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp7k9_mku"/><circle class="btu4zi_dc"/><path class="xcbtxr5ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-question" {...props}></Icon>
