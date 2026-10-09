<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz03g9rra.css';
import '../../css/k/kz2zzrs0w.css';
import '../../css/a/a_pbj0bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pz03g9rra"/><path class="kz2zzrs0w"/><path class="a_pbj0bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-20" {...props}></Icon>
