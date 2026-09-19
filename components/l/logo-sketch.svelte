<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drqt8gmkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="drqt8gmkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-sketch" {...props}></Icon>
