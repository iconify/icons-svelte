<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noom4acdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="noom4acdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:compass-solid" {...props}></Icon>
