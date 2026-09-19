<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb_nlublp.css';
import '../../css/b/bpfa_z1vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tb_nlublp"/><path class="bpfa_z1vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-log-in" {...props}></Icon>
