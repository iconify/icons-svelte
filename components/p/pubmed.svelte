<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmar4pbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmar4pbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pubmed" {...props}></Icon>
