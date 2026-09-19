<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czacm9bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="czacm9bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calendar-solid" {...props}></Icon>
