<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yevwt22qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yevwt22qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-smile-sharp-fill" {...props}></Icon>
