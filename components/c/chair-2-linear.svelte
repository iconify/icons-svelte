<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/smxycjv8r.css';
import '../../css/y/yg5kv2hph.css';
import '../../css/o/o3owdebtz.css';
import '../../css/w/wpt4tnb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="smxycjv8r"/><path class="yg5kv2hph"/><path class="o3owdebtz"/><path class="wpt4tnb6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chair-2-linear" {...props}></Icon>
