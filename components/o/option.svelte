<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b5164f7lr.css';
import '../../css/p/py6b5zbjb.css';
import '../../css/y/y59jr9jhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<g class="cuyn6tgcc"><path class="b5164f7lr"/><circle class="py6b5zbjb"/><circle class="y59jr9jhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:option" {...props}></Icon>
