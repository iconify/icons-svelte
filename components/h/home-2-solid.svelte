<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlc7xz5lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mlc7xz5lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:home-2-solid" {...props}></Icon>
