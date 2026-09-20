<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc0url8kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bc0url8kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:microwave-solid" {...props}></Icon>
