<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trikf9bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trikf9bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:corner-down-right" {...props}></Icon>
