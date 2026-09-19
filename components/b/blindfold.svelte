<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8s0vi_yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k8s0vi_yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:blindfold" {...props}></Icon>
