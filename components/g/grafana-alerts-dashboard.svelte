<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox-vypt0m.css';
import '../../css/i/ihwfk3vlx.css';
import '../../css/m/myw91kb6b.css';
import '../../css/y/ykrlmxbtw.css';
import '../../css/y/yk-zceb1c.css';
import '../../css/b/b7pjspbss.css';
import '../../css/o/o6sy6lbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ox-vypt0m"/><path class="ihwfk3vlx"/><path class="myw91kb6b"/><path class="ykrlmxbtw"/><circle class="yk-zceb1c"/><path class="b7pjspbss"/><path class="o6sy6lbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-alerts-dashboard" {...props}></Icon>
