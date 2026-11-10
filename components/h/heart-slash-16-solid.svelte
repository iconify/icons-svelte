<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slbc6rgwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="slbc6rgwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:heart-slash-16-solid" {...props}></Icon>
