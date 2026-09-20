<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3x2j_b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g3x2j_b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:earpods-solid" {...props}></Icon>
