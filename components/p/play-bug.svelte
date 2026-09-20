<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shu-v_b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shu-v_b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-bug" {...props}></Icon>
