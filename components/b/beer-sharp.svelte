<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii-zvlbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ii-zvlbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:beer-sharp" {...props}></Icon>
