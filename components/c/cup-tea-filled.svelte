<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkk8debim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkk8debim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cup-tea-filled" {...props}></Icon>
