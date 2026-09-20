<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9_jtcbed.css';
import '../../css/b/b1uw7cbks.css';
import '../../css/q/qd2rdm9ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9_jtcbed"/><path class="b1uw7cbks"/><path class="qd2rdm9ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bridge" {...props}></Icon>
