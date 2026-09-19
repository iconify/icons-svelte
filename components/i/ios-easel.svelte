<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl0tk0yor.css';
import '../../css/d/dxlqy5r4v.css';
import '../../css/u/um2eyh0wt.css';
import '../../css/q/q69a3ybwa.css';
import '../../css/k/kg7sicqni.css';
import '../../css/p/p7jik87kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gl0tk0yor"/><path class="dxlqy5r4v"/><path class="um2eyh0wt"/><g><path class="q69a3ybwa"/><path class="kg7sicqni"/></g><path class="p7jik87kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-easel" {...props}></Icon>
