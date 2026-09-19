<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeo6el_jt.css';
import '../../css/o/op5c-pbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeo6el_jt"/><path class="op5c-pbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:analyse" {...props}></Icon>
