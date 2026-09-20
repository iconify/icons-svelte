<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea4t3sg4a.css';
import '../../css/t/t-4jncuxe.css';
import '../../css/y/y9gfqabgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ea4t3sg4a"/><path class="t-4jncuxe"/><path class="y9gfqabgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:orientation" {...props}></Icon>
