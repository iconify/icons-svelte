<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z16gh80jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z16gh80jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:left-circle-solid" {...props}></Icon>
