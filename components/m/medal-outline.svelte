<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az58icbrr.css';
import '../../css/e/eezgffbcj.css';
import '../../css/z/z9r7tyb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="az58icbrr"/><circle class="eezgffbcj"/><path class="z9r7tyb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:medal-outline" {...props}></Icon>
