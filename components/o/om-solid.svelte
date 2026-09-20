<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1kek3bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j1kek3bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:om-solid" {...props}></Icon>
