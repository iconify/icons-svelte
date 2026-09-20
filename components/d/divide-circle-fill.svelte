<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faioegb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faioegb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:divide-circle-fill" {...props}></Icon>
