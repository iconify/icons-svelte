<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwrtmg0fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="lwrtmg0fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:grid" {...props}></Icon>
