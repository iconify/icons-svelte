<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abut1pzvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="abut1pzvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:layout-f" {...props}></Icon>
