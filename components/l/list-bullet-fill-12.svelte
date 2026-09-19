<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w50n8w_nj.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e-lv0wbnb.css';
import '../../css/s/sk2yvlahd.css';
import '../../css/a/albdd0b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="w50n8w_nj"/><g class="cuyn6tgcc"><circle class="e-lv0wbnb"/><circle class="sk2yvlahd"/><circle class="albdd0b6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-bullet-fill-12" {...props}></Icon>
