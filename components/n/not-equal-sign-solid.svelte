<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgpjj0r1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cgpjj0r1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:not-equal-sign-solid" {...props}></Icon>
