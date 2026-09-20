<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk_lobjkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk_lobjkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:app-window-filled" {...props}></Icon>
