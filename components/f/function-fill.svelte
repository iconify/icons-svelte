<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-xbpcb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-xbpcb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:function-fill" {...props}></Icon>
