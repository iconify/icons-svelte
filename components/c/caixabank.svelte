<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7a09-mtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7a09-mtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:caixabank" {...props}></Icon>
