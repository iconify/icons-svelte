<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7ej__5_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j7ej__5_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:erlenmeyer-flask-solid" {...props}></Icon>
