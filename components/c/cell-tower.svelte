<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6ch6q6dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l6ch6q6dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cell-tower" {...props}></Icon>
