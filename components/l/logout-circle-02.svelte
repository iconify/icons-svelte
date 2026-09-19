<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwj3tybzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwj3tybzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:logout-circle-02" {...props}></Icon>
