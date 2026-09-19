<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcffhsb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":690,"height":718};
const content = `<path class="hcffhsb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:arrowright" {...props}></Icon>
