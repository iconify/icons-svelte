<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul6au0wgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul6au0wgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-function" {...props}></Icon>
