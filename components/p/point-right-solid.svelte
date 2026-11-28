<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8j2874re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8j2874re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:point-right-solid" {...props}></Icon>
