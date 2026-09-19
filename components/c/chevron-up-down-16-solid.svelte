<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyh-ry88k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vyh-ry88k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-up-down-16-solid" {...props}></Icon>
