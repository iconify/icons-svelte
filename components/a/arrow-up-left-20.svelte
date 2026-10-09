<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hehatfcph.css';
import '../../css/a/ayea-y_zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hehatfcph"/><path class="ayea-y_zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-left-20" {...props}></Icon>
