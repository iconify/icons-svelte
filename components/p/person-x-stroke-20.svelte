<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv0u75bem.css';
import '../../css/z/zplth4i-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xv0u75bem"/><path class="zplth4i-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-x-stroke-20" {...props}></Icon>
