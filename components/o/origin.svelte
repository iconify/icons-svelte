<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfqu-9b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mfqu-9b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:origin" {...props}></Icon>
