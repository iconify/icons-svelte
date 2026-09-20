<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lswo68b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lswo68b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:moq" {...props}></Icon>
