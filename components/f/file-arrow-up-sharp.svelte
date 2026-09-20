<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0ycukbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0ycukbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-arrow-up-sharp" {...props}></Icon>
