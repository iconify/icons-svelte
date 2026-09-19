<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt1kn2zpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vt1kn2zpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:book-medical" {...props}></Icon>
