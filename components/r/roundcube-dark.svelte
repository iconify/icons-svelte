<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6ctizbcx.css';
import '../../css/m/m8et6-xvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e6ctizbcx"/><path class="m8et6-xvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:roundcube-dark" {...props}></Icon>
