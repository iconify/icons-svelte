<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0zrdacze.css';
import '../../css/y/ytt2rub5i.css';
import '../../css/x/x0ucnnbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d0zrdacze"/><path class="ytt2rub5i"/><path class="x0ucnnbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kmeet-light" {...props}></Icon>
