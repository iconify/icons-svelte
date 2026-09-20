<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yarre3bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yarre3bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gender-agender" {...props}></Icon>
