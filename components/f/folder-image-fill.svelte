<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmj--94hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmj--94hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-image-fill" {...props}></Icon>
