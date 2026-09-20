<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar2gvbdfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ar2gvbdfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:compass-alt-fill" {...props}></Icon>
