<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eht1iybet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eht1iybet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-edit" {...props}></Icon>
