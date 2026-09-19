<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqwr_sfrm.css';
import '../../css/i/i6wr-kbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqwr_sfrm"/><path class="i6wr-kbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:lock-outline" {...props}></Icon>
