<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my-29jn8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my-29jn8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:list-checkmark" {...props}></Icon>
