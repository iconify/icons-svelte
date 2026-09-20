<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c72y3bcyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c72y3bcyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:customer-support-1-solid" {...props}></Icon>
