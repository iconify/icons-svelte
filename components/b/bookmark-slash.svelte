<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssl67mbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssl67mbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bookmark-slash" {...props}></Icon>
