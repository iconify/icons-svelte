<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfc3txbai.css';
import '../../css/f/f43eqhbwn.css';
import '../../css/y/yx6wxur-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dfc3txbai"/><circle class="f43eqhbwn"/><path clip-rule="evenodd" class="yx6wxur-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:geopoint" {...props}></Icon>
