<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcyxmuqez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":443,"height":512};
const content = `<path class="zcyxmuqez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pyup" {...props}></Icon>
