<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgvez0b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kgvez0b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:projector-solid" {...props}></Icon>
