<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmbsh3b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmbsh3b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cursor-text" {...props}></Icon>
