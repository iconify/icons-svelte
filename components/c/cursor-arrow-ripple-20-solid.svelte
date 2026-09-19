<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gnv5hp48c.css';
import '../../css/c/cdqyxub-y.css';
import '../../css/k/k53w0sboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="gnv5hp48c"/><path class="cdqyxub-y"/><path class="k53w0sboq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cursor-arrow-ripple-20-solid" {...props}></Icon>
