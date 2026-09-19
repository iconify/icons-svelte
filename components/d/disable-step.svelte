<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmay3mwzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gmay3mwzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:disable-step" {...props}></Icon>
