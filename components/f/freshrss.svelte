<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb5b0n5vc.css';
import '../../css/b/bcvzlnbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mb5b0n5vc"/><path class="bcvzlnbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freshrss" {...props}></Icon>
