<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akwh0bb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akwh0bb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flask-2-filled" {...props}></Icon>
