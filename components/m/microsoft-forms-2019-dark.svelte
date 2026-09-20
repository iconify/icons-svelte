<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an70hubtx.css';
import '../../css/o/o4h750biq.css';
import '../../css/k/k5yy91bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="an70hubtx"/><path class="o4h750biq"/><path class="k5yy91bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-forms-2019-dark" {...props}></Icon>
