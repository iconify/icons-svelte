<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0xa18b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="h0xa18b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:delete" {...props}></Icon>
