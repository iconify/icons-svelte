<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7_7-h00t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7_7-h00t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:leafs" {...props}></Icon>
