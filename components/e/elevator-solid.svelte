<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glyhv4jss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="glyhv4jss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:elevator-solid" {...props}></Icon>
