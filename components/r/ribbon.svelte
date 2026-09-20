<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bf5_xfbow.css';
import '../../css/d/die8b53tm.css';
import '../../css/l/lx9jh7bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bf5_xfbow"/><path class="die8b53tm"/><path class="lx9jh7bof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:ribbon" {...props}></Icon>
