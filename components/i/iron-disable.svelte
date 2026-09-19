<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/a/aqhc3dbwk.css';
import '../../css/b/bpfzin4my.css';
import '../../css/t/t3uvdxkip.css';
import '../../css/d/dx786oc2c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnMPCneHY"><g class="wwvp95byt"><path class="aqhc3dbwk"/><path class="bpfzin4my"/><circle class="t3uvdxkip"/><path class="dx786oc2c"/></g></mask></defs><path mask="url(#SVGnMPCneHY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:iron-disable" {...props}></Icon>
