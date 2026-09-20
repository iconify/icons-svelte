<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmkza5_pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmkza5_pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:equal" {...props}></Icon>
