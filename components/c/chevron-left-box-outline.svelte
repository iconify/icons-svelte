<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkh4p1ded.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkh4p1ded"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-left-box-outline" {...props}></Icon>
