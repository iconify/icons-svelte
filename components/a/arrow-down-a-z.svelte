<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh6o4c0gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh6o4c0gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-a-z" {...props}></Icon>
