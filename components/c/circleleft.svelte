<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj7fhcc0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dj7fhcc0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleleft" {...props}></Icon>
