<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doijq24oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doijq24oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-del-light" {...props}></Icon>
