<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/b7-l3ptxy.css';
import '../../css/b/bd2-kmgzj.css';
import '../../css/t/t8h1t8byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7-l3ptxy"/><path class="bd2-kmgzj"/><path class="t8h1t8byf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:printer" {...props}></Icon>
