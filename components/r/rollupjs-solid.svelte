<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_avgdczx.css';
import '../../css/k/kc709bcob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l_avgdczx"/><path class="kc709bcob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:rollupjs-solid" {...props}></Icon>
