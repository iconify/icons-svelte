<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kz9epiigo.css';
import '../../css/m/mswo_dbyo.css';
import '../../css/p/pltokbbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><circle class="kz9epiigo"/><circle class="mswo_dbyo"/><path class="pltokbbut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flickr-square" {...props}></Icon>
