<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuzco31ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zuzco31ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:folder-open" {...props}></Icon>
