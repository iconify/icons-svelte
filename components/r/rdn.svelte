<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aue3nn3gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aue3nn3gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:rdn" {...props}></Icon>
