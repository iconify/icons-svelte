<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj4znacmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj4znacmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:presentation" {...props}></Icon>
