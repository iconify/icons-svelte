<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/litncn_oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="litncn_oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:eye-optic-solid" {...props}></Icon>
