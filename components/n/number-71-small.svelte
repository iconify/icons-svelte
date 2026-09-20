<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-58qssej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-58qssej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-71-small" {...props}></Icon>
