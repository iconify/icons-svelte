<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj9dx5mvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj9dx5mvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:loader" {...props}></Icon>
