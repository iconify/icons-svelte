<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydne_bc6v.css';
import '../../css/b/bf53s552u.css';
import '../../css/c/chv70ybrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ydne_bc6v"><path class="bf53s552u"/><path class="chv70ybrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ai-science-robot" {...props}></Icon>
