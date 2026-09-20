<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxgdie26v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rxgdie26v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:erlenmeyer-flask-solid" {...props}></Icon>
