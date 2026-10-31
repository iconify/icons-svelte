<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ita8ud3ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ita8ud3ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:robot-solid" {...props}></Icon>
