<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnwxchu1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mnwxchu1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:diamond-2-solid" {...props}></Icon>
