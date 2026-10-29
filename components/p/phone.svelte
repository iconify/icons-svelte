<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwk0k-bfu.css';
import '../../css/h/hzn7y5udb.css';
import '../../css/d/dvhdx5bfq.css';
import '../../css/s/sx667fd1s.css';
import '../../css/e/ea0xpgcru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwk0k-bfu wm-shadow"/><path class="hzn7y5udb wm-k"/><path class="dvhdx5bfq wm-a"/><path class="sx667fd1s wm-deco"/><path class="ea0xpgcru wm-shine"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:phone" {...props}></Icon>
