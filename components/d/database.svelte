<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhkr7jb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="fhkr7jb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:database" {...props}></Icon>
