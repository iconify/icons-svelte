<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqae8lbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqae8lbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:inbox2" {...props}></Icon>
