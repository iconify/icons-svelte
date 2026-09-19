<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvw95zb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvw95zb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-remove-02" {...props}></Icon>
