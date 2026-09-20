<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7_0c7bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7_0c7bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:eye-dotted" {...props}></Icon>
