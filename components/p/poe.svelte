<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b75_w6b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b75_w6b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:poe" {...props}></Icon>
