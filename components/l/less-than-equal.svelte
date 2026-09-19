<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfmvkpkva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zfmvkpkva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:less-than-equal" {...props}></Icon>
