<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzn5g7ntz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzn5g7ntz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:lamp-03" {...props}></Icon>
