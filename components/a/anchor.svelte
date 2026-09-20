<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex2-leshc.css';
import '../../css/k/kg2uyccfb.css';
import '../../css/y/y1nytpm2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex2-leshc"/><path class="kg2uyccfb"/><path class="y1nytpm2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:anchor" {...props}></Icon>
