<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i10t6p7pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i10t6p7pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:flydotio" {...props}></Icon>
