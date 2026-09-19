<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka6fx8hhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka6fx8hhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-security" {...props}></Icon>
