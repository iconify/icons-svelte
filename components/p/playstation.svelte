<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqkqu1blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="uqkqu1blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:playstation" {...props}></Icon>
