<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y260qjo9u.css';
import '../../css/k/kvtyxvn8k.css';
import '../../css/y/yj-rpobms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<circle class="y260qjo9u"/><circle class="kvtyxvn8k"/><path class="yj-rpobms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:grocery-or-supermarket" {...props}></Icon>
