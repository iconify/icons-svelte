<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9ejun91r.css';
import '../../css/z/zb03b0nag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k9ejun91r"/><path class="zb03b0nag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:evergreen" {...props}></Icon>
