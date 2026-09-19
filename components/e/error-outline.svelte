<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaecykbpq.css';
import '../../css/c/cpwp98h5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jaecykbpq"/><path class="cpwp98h5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:error-outline" {...props}></Icon>
