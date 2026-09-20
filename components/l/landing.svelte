<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5e9y-bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5e9y-bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:landing" {...props}></Icon>
