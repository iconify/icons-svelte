<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7agjebmg.css';
import '../../css/q/qr18a0v8s.css';
import '../../css/d/d7fm7dbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q7agjebmg"/><path class="qr18a0v8s"/><path class="d7fm7dbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-mail-light" {...props}></Icon>
