<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnawge0py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnawge0py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:book-open" {...props}></Icon>
