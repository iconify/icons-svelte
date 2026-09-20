<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt922oa_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bt922oa_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:google" {...props}></Icon>
