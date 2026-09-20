<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb3fmqb9r.css';
import '../../css/g/g03kqebpl.css';
import '../../css/o/o-m9f6foy.css';
import '../../css/a/aq5nklx-g.css';
import '../../css/t/tmsmu8bek.css';
import '../../css/c/c-rmwybji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qb3fmqb9r"/><path class="g03kqebpl"/><path class="o-m9f6foy"/><circle transform="rotate(-80.781 256.004 228.196)" class="aq5nklx-g"/><path class="tmsmu8bek"/><path class="c-rmwybji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:geopulse-light" {...props}></Icon>
