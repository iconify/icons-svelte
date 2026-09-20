<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqipizbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqipizbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:hanger-flat" {...props}></Icon>
