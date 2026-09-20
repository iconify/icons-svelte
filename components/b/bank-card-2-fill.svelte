<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5aa9x36e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5aa9x36e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bank-card-2-fill" {...props}></Icon>
