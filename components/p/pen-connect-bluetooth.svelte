<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsih-mv_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsih-mv_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pen-connect-bluetooth" {...props}></Icon>
