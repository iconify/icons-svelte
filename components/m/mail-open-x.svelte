<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm5mdouze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm5mdouze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-open-x" {...props}></Icon>
