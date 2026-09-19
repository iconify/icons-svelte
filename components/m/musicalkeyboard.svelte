<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql__uvuun.css';
import '../../css/m/m42qaacec.css';
import '../../css/p/pmct9tb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ql__uvuun"/><path class="m42qaacec"/><path class="pmct9tb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:musicalkeyboard" {...props}></Icon>
