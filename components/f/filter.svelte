<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdrb4cbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdrb4cbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:filter" {...props}></Icon>
