<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufyxqz38e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufyxqz38e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-remove" {...props}></Icon>
