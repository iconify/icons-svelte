<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq9167bja.css';
import '../../css/m/m744oxfrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qq9167bja"/><path class="m744oxfrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kerbside-charger-20" {...props}></Icon>
