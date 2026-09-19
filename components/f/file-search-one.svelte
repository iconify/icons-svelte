<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/w/wp78-jzxc.css';
import '../../css/e/eb6et-bht.css';
import '../../css/t/t4gy73cxx.css';
import '../../css/p/pw33lubvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="wp78-jzxc"/><circle class="eb6et-bht"/><path class="t4gy73cxx"/><path class="pw33lubvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:file-search-one" {...props}></Icon>
