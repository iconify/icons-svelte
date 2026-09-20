<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef_udb4nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef_udb4nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:eye-close-fill" {...props}></Icon>
