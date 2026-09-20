<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkrpub5im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-11};
const content = `<path class="zkrpub5im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:minus" {...props}></Icon>
