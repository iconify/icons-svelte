<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5oo-jpmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="h5oo-jpmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:align-justify" {...props}></Icon>
