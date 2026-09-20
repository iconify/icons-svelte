<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toh4a7b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="toh4a7b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-more-vertical-fill" {...props}></Icon>
