<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csgxesbgh.css';
import '../../css/c/ctzgkpf1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csgxesbgh"/><path class="ctzgkpf1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:calendar-star-solid" {...props}></Icon>
