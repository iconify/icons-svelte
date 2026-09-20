<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feyhq7vpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feyhq7vpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoftonenote" {...props}></Icon>
