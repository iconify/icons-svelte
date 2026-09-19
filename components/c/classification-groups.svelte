<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfuw7jbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mfuw7jbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:classification-groups" {...props}></Icon>
