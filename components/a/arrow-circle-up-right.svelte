<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlt5bcb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vlt5bcb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-circle-up-right" {...props}></Icon>
