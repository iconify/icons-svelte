<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3h0-u43f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3h0-u43f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-code-search" {...props}></Icon>
