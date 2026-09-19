<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v67dzhjys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":334,"height":512};
const content = `<path class="v67dzhjys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:brakeman" {...props}></Icon>
