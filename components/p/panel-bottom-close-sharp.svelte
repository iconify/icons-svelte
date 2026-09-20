<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9s53f24b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9s53f24b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-close-sharp" {...props}></Icon>
