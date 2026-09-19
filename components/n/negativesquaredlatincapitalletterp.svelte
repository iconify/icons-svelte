<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4xf1bb5l.css';
import '../../css/r/r8hexeb-r.css';
import '../../css/l/l06dicexc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o4xf1bb5l"/><path class="r8hexeb-r"/><path class="l06dicexc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:negativesquaredlatincapitalletterp" {...props}></Icon>
