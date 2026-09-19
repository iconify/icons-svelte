<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw5wgw3nd.css';
import '../../css/u/u2bmd6bte.css';
import '../../css/v/vl6kuv2by.css';
import '../../css/s/s6c_7lb9q.css';
import '../../css/z/z7c3p7bxa.css';
import '../../css/r/rgs_dyyyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw5wgw3nd"/><path class="u2bmd6bte"/><path class="vl6kuv2by"/><path class="s6c_7lb9q"/><path class="z7c3p7bxa"/><path class="rgs_dyyyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:connectors" {...props}></Icon>
