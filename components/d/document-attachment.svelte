<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq7h70pom.css';
import '../../css/y/y3ymk3bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eq7h70pom"/><path class="y3ymk3bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-attachment" {...props}></Icon>
