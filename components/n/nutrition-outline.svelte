<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e9dlq0bzy.css';
import '../../css/i/iy41s3vjl.css';
import '../../css/g/g8w6-jmaw.css';
import '../../css/q/qpbo7bcqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="e9dlq0bzy"/><path class="iy41s3vjl"/><path clip-rule="evenodd" class="g8w6-jmaw"/><path class="qpbo7bcqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:nutrition-outline" {...props}></Icon>
