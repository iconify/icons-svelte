<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7rfvudmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7rfvudmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading" {...props}></Icon>
