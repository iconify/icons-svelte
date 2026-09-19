<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tal1vmb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tal1vmb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-up-down-16-solid" {...props}></Icon>
