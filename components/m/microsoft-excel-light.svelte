<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvmnxt6ft.css';
import '../../css/m/mkor83bnq.css';
import '../../css/m/m8r9zubhb.css';
import '../../css/y/y1mciqk_m.css';
import '../../css/d/dbqjt5bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hvmnxt6ft"/><path class="mkor83bnq"/><path class="m8r9zubhb"/><path class="y1mciqk_m"/><path class="dbqjt5bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-excel-light" {...props}></Icon>
