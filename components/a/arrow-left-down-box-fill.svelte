<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1zz_mb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1zz_mb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-down-box-fill" {...props}></Icon>
