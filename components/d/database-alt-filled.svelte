<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov3qt0kxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ov3qt0kxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:database-alt-filled" {...props}></Icon>
