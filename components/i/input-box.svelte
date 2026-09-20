<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy80e3meu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sy80e3meu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:input-box" {...props}></Icon>
