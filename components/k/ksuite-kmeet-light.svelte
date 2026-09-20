<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc6ttac-i.css';
import '../../css/k/kysr9_zzg.css';
import '../../css/x/x0ucnnbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yc6ttac-i"/><path class="kysr9_zzg"/><path class="x0ucnnbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kmeet-light" {...props}></Icon>
