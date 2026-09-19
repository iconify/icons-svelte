<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw25tvi6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tw25tvi6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-snow-fill" {...props}></Icon>
