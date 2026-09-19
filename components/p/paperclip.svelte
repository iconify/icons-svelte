<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smx2kur-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="smx2kur-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:paperclip" {...props}></Icon>
