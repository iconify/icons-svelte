<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0qvv3bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c0qvv3bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bch" {...props}></Icon>
