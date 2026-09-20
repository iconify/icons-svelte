<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdsia9gjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdsia9gjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:input-box" {...props}></Icon>
