<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh8pb8bip.css';
import '../../css/i/iq88sthgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xh8pb8bip"/><path class="iq88sthgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-check-20" {...props}></Icon>
