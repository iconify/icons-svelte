<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo0oht-lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo0oht-lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-horizontal" {...props}></Icon>
