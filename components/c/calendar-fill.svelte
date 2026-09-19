<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ony59q43f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ony59q43f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:calendar-fill" {...props}></Icon>
