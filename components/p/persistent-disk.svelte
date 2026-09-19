<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm_i66_ym.css';
import '../../css/o/ojwmqkoww.css';
import '../../css/x/xrhdcypyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm_i66_ym"/><path class="ojwmqkoww"/><path class="xrhdcypyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:persistent-disk" {...props}></Icon>
