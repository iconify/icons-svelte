<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq14b5_xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rq14b5_xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diary-fill" {...props}></Icon>
