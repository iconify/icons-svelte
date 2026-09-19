<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewe25tbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewe25tbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-3-square-thin" {...props}></Icon>
