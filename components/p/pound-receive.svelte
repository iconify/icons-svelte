<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te8h4cyoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te8h4cyoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pound-receive" {...props}></Icon>
