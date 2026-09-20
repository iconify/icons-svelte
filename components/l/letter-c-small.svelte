<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_1c3bbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_1c3bbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-c-small" {...props}></Icon>
