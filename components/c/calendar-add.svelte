<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlcca801u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlcca801u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:calendar-add" {...props}></Icon>
