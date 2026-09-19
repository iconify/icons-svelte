<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh5c8rm5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="jh5c8rm5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:industry" {...props}></Icon>
