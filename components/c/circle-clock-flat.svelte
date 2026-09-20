<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e8psh3biy.css';
import '../../css/n/n-t92abvs.css';
import '../../css/c/c-24taceb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="e8psh3biy"/><path class="n-t92abvs"/><path class="c-24taceb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:circle-clock-flat" {...props}></Icon>
