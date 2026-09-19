<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsp58bb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jsp58bb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:radio-16-solid" {...props}></Icon>
