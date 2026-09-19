<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu641e4zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu641e4zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heading-1" {...props}></Icon>
