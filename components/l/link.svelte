<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0c1uhphr.css';
import '../../css/k/kx2q3nbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d0c1uhphr"/><path class="kx2q3nbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:link" {...props}></Icon>
