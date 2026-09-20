<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v568gcbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="v568gcbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:linkedin-solid" {...props}></Icon>
