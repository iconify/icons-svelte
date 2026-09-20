<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fossa55ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="fossa55ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:minus" {...props}></Icon>
