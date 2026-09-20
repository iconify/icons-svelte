<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1vs7vpjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1vs7vpjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:caret-right-sharp-duotone" {...props}></Icon>
