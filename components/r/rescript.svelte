<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsemo4tci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsemo4tci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rescript" {...props}></Icon>
