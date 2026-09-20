<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oam8hmbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oam8hmbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bacteria-virus-cells-biology-solid" {...props}></Icon>
