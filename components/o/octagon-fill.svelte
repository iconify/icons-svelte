<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx9w79bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kx9w79bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:octagon-fill" {...props}></Icon>
