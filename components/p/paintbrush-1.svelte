<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er16xtb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="er16xtb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:paintbrush-1" {...props}></Icon>
