<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os6ggdb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os6ggdb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:road-off" {...props}></Icon>
