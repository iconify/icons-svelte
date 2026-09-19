<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f90d6rh1v.css';
import '../../css/g/g-i8fs05n.css';
import '../../css/k/kv6qicbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f90d6rh1v"/><path class="g-i8fs05n"/><path class="kv6qicbin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:node-edit" {...props}></Icon>
