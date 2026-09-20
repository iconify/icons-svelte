<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeqf11zww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeqf11zww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-plus-outline" {...props}></Icon>
