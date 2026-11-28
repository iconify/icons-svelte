<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yryz9-i4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yryz9-i4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:credit-card-lock" {...props}></Icon>
