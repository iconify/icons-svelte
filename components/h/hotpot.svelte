<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7nz9-bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="k7nz9-bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:hotpot" {...props}></Icon>
