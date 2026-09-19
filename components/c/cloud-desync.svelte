<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hvyo4034m.css';
import '../../css/m/mv30-1c_a.css';
import '../../css/j/jn1qofb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hvyo4034m"/><path class="mv30-1c_a"/><path class="jn1qofb9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cloud-desync" {...props}></Icon>
