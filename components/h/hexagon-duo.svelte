<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tryzyvb9o.css';
import '../../css/k/kftm6xogs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tryzyvb9o"/><path class="kftm6xogs primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hexagon-duo" {...props}></Icon>
