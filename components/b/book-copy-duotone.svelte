<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zj1i-8bco.css';
import '../../css/h/hxjy4jbwr.css';
import '../../css/d/d2fkh4b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zj1i-8bco"/><path class="hxjy4jbwr"/><path class="d2fkh4b7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-copy-duotone" {...props}></Icon>
