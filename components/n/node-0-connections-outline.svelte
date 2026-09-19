<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/n/nodca_-dr.css';
import '../../css/m/mwe-9d8rn.css';
import '../../css/s/sm9mn1yft.css';
import '../../css/j/jt095ubsn.css';
import '../../css/t/tvibfoxqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="nodca_-dr"/><circle class="mwe-9d8rn"/><circle class="sm9mn1yft"/><circle class="jt095ubsn"/><circle class="tvibfoxqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:node-0-connections-outline" {...props}></Icon>
