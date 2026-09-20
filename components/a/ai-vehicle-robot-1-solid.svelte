<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3q9vzbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c3q9vzbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ai-vehicle-robot-1-solid" {...props}></Icon>
