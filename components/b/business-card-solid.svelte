<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmf4h2brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pmf4h2brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:business-card-solid" {...props}></Icon>
