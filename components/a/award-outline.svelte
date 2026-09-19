<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anhm5qwyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anhm5qwyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:award-outline" {...props}></Icon>
