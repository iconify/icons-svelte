<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so70jzd9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="so70jzd9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:full-screen-osx-solid" {...props}></Icon>
