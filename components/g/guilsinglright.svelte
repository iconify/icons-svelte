<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu3kytnrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":516,"height":614};
const content = `<path class="hu3kytnrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:guilsinglright" {...props}></Icon>
