<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eafkvu7mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eafkvu7mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-circle-solid" {...props}></Icon>
