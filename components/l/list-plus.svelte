<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zidbk5d5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zidbk5d5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:list-plus" {...props}></Icon>
