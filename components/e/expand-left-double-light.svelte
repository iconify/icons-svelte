<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivymxac-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivymxac-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-left-double-light" {...props}></Icon>
