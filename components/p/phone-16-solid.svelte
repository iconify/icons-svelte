<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd9qg0nen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nd9qg0nen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:phone-16-solid" {...props}></Icon>
