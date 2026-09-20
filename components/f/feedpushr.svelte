<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee3_s121s.css';
import '../../css/x/xyl9rzbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ee3_s121s"/><path class="xyl9rzbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feedpushr" {...props}></Icon>
