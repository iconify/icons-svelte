<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmzwvgbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmzwvgbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:recycle-02" {...props}></Icon>
