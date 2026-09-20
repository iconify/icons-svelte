<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2tbuyb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x2tbuyb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:buildings-2-filled" {...props}></Icon>
