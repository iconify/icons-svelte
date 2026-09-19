<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueksp0b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueksp0b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:leaf-filled" {...props}></Icon>
