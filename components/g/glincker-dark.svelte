<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar1skxb1o.css';
import '../../css/q/q35s5pbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":375,"height":375};
const content = `<path class="ar1skxb1o"/><path class="q35s5pbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:glincker-dark" {...props}></Icon>
