<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f70-5sbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f70-5sbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:keybase" {...props}></Icon>
