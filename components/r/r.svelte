<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4-xwobuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j4-xwobuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:r" {...props}></Icon>
