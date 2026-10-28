<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bio0il38c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bio0il38c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-left" {...props}></Icon>
