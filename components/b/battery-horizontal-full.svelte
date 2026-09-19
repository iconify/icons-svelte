<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjtxg3s9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjtxg3s9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:battery-horizontal-full" {...props}></Icon>
