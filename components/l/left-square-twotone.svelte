<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc8-4tb2b.css';
import '../../css/l/l-_1mtbvg.css';
import '../../css/q/q2-__fzdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="l-_1mtbvg"/><path class="q2-__fzdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:left-square-twotone" {...props}></Icon>
