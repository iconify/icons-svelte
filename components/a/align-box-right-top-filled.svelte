<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncxz46buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncxz46buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-right-top-filled" {...props}></Icon>
