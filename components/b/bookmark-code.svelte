<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzxuuccwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzxuuccwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-code" {...props}></Icon>
