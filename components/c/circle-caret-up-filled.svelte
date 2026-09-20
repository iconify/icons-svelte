<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur4f7_bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur4f7_bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-caret-up-filled" {...props}></Icon>
