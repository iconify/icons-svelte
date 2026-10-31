<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8g66mkzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8g66mkzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-round" {...props}></Icon>
