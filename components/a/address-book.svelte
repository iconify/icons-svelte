<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-20n0bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="q-20n0bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:address-book" {...props}></Icon>
