<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsen8tbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hsen8tbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:grid-filled" {...props}></Icon>
