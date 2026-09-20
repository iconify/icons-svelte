<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xck5rbc3z.css';
import '../../css/e/edd2mwbun.css';
import '../../css/m/me0q1cc4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="edd2mwbun"/><path class="me0q1cc4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pencil-square" {...props}></Icon>
