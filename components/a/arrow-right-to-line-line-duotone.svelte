<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/tgvfhnabb.css';
import '../../css/p/p2xi9gwtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tgvfhnabb"/><path class="p2xi9gwtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-to-line-line-duotone" {...props}></Icon>
