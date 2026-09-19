<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw50q5sdt.css';
import '../../css/t/tcsakibxe.css';
import '../../css/x/xoc373bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aw50q5sdt"/><path class="tcsakibxe"/><path class="xoc373bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-filing" {...props}></Icon>
