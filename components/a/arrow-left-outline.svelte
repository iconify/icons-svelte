<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvbrmmbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvbrmmbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:arrow-left-outline" {...props}></Icon>
