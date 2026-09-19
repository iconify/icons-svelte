<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnvuzvbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnvuzvbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:grid-big" {...props}></Icon>
