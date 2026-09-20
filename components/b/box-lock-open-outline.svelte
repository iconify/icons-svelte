<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn66o2gqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn66o2gqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-lock-open-outline" {...props}></Icon>
