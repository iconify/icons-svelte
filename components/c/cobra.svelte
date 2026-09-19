<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk5o4h72k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bk5o4h72k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cobra" {...props}></Icon>
