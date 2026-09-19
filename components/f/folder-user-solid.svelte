<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4s7d7bjc.css';
import '../../css/s/sz_qvhbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4s7d7bjc"/><path class="sz_qvhbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-user-solid" {...props}></Icon>
