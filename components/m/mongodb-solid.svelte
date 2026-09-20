<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmt-5dbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cmt-5dbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mongodb-solid" {...props}></Icon>
