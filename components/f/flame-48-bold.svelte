<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1y455t_n.css';
import '../../css/c/cqs0s2txc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k1y455t_n"/><path class="cqs0s2txc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flame-48-bold" {...props}></Icon>
