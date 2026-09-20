<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-9a52u1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n-9a52u1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fire-extinguisher-sign-solid" {...props}></Icon>
