<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsm3uwb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsm3uwb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:block" {...props}></Icon>
