<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbru06b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbru06b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevron-left-fill" {...props}></Icon>
