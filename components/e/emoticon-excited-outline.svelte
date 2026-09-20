<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee0klhbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee0klhbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-excited-outline" {...props}></Icon>
