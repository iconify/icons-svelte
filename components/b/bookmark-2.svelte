<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el1a2nwhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="el1a2nwhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bookmark-2" {...props}></Icon>
