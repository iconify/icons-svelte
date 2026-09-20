<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu-98sbyh.css';
import '../../css/k/kpvxz2bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu-98sbyh"/><path class="kpvxz2bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:door-open" {...props}></Icon>
