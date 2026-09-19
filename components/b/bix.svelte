<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ir4y4fk6l.css';
import '../../css/b/blxps4bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="ir4y4fk6l"/><path class="blxps4bai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:bix" {...props}></Icon>
