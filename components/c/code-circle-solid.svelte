<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phqe5zbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phqe5zbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:code-circle-solid" {...props}></Icon>
