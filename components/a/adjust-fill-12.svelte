<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc-hat22k.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ae87yac1j.css';
import '../../css/g/gh288vdeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oc-hat22k"/><g class="cuyn6tgcc"><circle class="ae87yac1j"/><circle class="gh288vdeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:adjust-fill-12" {...props}></Icon>
