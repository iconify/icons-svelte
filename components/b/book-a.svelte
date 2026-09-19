<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wnxln3bbv.css';
import '../../css/i/icjlvdb0c.css';
import '../../css/z/zlhh38l7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wnxln3bbv"/><path class="icjlvdb0c"/><path class="zlhh38l7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:book-a" {...props}></Icon>
