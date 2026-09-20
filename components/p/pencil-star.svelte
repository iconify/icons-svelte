<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciy7lrb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ciy7lrb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-star" {...props}></Icon>
