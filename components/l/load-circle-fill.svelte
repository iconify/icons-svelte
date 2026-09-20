<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inx9gng5o.css';
import '../../css/w/wrhz-zbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inx9gng5o"/><path class="wrhz-zbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:load-circle-fill" {...props}></Icon>
