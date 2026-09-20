<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aymoarswq.css';
import '../../css/e/etmdw1btw.css';
import '../../css/k/ka2hejb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aymoarswq"/><path class="etmdw1btw"/><path class="ka2hejb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qnap" {...props}></Icon>
