<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-dmpsp-p.css';
import '../../css/n/n2fkhdu9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g-dmpsp-p"/><path class="n2fkhdu9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:layers-external" {...props}></Icon>
