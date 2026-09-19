<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8cxui63k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8cxui63k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:checkbox-filled" {...props}></Icon>
