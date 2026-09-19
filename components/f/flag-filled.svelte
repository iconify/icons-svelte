<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtjwq6hha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mtjwq6hha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flag-filled" {...props}></Icon>
