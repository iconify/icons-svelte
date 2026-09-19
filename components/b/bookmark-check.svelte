<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zioed6fcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zioed6fcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bookmark-check" {...props}></Icon>
