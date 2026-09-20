<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt5_813gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gt5_813gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:box-sign-solid" {...props}></Icon>
