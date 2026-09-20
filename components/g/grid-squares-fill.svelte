<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/funl9eb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="funl9eb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-squares-fill" {...props}></Icon>
