<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwirp0b1q.css';
import '../../css/e/efcc7ncew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwirp0b1q"/><path clip-rule="evenodd" class="efcc7ncew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-charge-outline" {...props}></Icon>
