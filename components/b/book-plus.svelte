<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz_fsnb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz_fsnb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-plus" {...props}></Icon>
