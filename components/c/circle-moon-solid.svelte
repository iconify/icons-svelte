<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb2xsdb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb2xsdb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-moon-solid" {...props}></Icon>
