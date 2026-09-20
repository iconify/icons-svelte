<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhogt5lio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhogt5lio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-pause" {...props}></Icon>
