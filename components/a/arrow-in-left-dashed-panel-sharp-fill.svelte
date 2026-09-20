<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnqo0zbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnqo0zbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-left-dashed-panel-sharp-fill" {...props}></Icon>
