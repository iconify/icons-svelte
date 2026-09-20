<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et40e2byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="et40e2byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ai-gaming-robot-solid" {...props}></Icon>
