<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymrpwkn1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ymrpwkn1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-favorite-heart-solid" {...props}></Icon>
