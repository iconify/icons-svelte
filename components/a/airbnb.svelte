<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqk-lo6pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zqk-lo6pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:airbnb" {...props}></Icon>
