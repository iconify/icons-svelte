<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weua4abnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weua4abnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-down-right-md" {...props}></Icon>
