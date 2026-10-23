<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otucgnd4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otucgnd4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bluetooth-searching" {...props}></Icon>
