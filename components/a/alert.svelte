<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0w00mqsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="c0w00mqsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:alert" {...props}></Icon>
