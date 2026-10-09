<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be6_u9f6k.css';
import '../../css/b/b_4t_bc2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="be6_u9f6k"/><path class="b_4t_bc2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pallet-48-bold" {...props}></Icon>
