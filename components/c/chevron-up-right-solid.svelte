<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in9j5j9wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in9j5j9wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-right-solid" {...props}></Icon>
