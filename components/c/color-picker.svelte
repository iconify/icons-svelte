<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u___c24ko.css';
import '../../css/d/de4-70ccf.css';
import '../../css/b/b63ipmk3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="u___c24ko"/><path clip-rule="evenodd" class="de4-70ccf"/><path class="b63ipmk3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:color-picker" {...props}></Icon>
