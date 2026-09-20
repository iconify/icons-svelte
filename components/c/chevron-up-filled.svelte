<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc_0qyjkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc_0qyjkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chevron-up-filled" {...props}></Icon>
