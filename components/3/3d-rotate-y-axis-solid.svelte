<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh8q-t_re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kh8q-t_re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:3d-rotate-y-axis-solid" {...props}></Icon>
