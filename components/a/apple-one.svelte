<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/uz5a9fb8c.css';
import '../../css/s/sqfsm7btn.css';
import '../../css/b/b98kc6bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="uz5a9fb8c"/><path class="sqfsm7btn"/><path class="b98kc6bwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:apple-one" {...props}></Icon>
