<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nktbh_b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nktbh_b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:h2-16-solid" {...props}></Icon>
