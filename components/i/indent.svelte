<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d61k69bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d61k69bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:indent" {...props}></Icon>
