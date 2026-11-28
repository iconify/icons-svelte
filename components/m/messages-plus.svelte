<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu_vczbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu_vczbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:messages-plus" {...props}></Icon>
