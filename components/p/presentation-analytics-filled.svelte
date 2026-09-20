<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7o6iqeuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7o6iqeuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:presentation-analytics-filled" {...props}></Icon>
