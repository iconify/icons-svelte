<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l10w-sbyp.css';
import '../../css/q/qrjc3lvtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l10w-sbyp"/><path class="qrjc3lvtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bed-double-solid" {...props}></Icon>
