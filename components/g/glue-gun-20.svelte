<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr0eqko7m.css';
import '../../css/q/q39gh2k1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hr0eqko7m"/><path class="q39gh2k1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glue-gun-20" {...props}></Icon>
