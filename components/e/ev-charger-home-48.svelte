<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaei814vi.css';
import '../../css/x/xwqlmeb2f.css';
import '../../css/i/i10hk57ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kaei814vi"/><path class="xwqlmeb2f"/><path class="i10hk57ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-home-48" {...props}></Icon>
