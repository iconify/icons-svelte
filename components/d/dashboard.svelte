<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0wpabctl.css';
import '../../css/n/nblgfwbys.css';
import '../../css/r/rcidtuiap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0wpabctl"/><path class="nblgfwbys"/><path class="rcidtuiap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:dashboard" {...props}></Icon>
