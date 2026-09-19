<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5cg8fb9r.css';
import '../../css/v/v7_zg0b3e.css';
import '../../css/e/eoes09bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="v7_zg0b3e"/><path class="eoes09bhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:boxing-one" {...props}></Icon>
