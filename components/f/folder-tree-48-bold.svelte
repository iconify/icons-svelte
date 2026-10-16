<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cws-8tb1t.css';
import '../../css/a/aktl5czru.css';
import '../../css/m/m86vp2brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cws-8tb1t"/><path class="aktl5czru"/><path class="m86vp2brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-tree-48-bold" {...props}></Icon>
