<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv8svybwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv8svybwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brightness-auto-filled" {...props}></Icon>
