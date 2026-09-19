<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pr22v6kld.css';
import '../../css/k/kq0341bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pr22v6kld"/><path class="kq0341bef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hierarchy-square-05" {...props}></Icon>
