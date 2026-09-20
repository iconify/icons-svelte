<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6sknbc3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6sknbc3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:layers" {...props}></Icon>
