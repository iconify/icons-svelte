<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak46xro0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak46xro0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-right-3-square-thin" {...props}></Icon>
