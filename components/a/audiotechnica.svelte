<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kppq0fbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kppq0fbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:audiotechnica" {...props}></Icon>
