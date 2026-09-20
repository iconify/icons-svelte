<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxe6p1gov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-2};
const content = `<path class="kxe6p1gov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:history" {...props}></Icon>
