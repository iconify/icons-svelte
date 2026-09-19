<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir9h4mb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ir9h4mb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-bar-filled" {...props}></Icon>
