<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/femfy8bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="femfy8bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-open" {...props}></Icon>
