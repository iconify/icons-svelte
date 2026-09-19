<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wadt5k89n.css';
import '../../css/l/li7_vqt7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wadt5k89n"/><path class="li7_vqt7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-alarm-outline" {...props}></Icon>
