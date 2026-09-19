<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0c_zi20n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":559,"height":854};
const content = `<path class="c0c_zi20n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:backslash" {...props}></Icon>
