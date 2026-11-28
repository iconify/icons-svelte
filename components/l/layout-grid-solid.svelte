<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsbuhiq7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsbuhiq7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layout-grid-solid" {...props}></Icon>
