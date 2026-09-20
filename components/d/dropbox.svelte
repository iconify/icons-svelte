<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkm6kxbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkm6kxbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dropbox" {...props}></Icon>
