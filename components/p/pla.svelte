<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x82e92b6s.css';
import '../../css/u/ubp77pb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x82e92b6s"/><path class="ubp77pb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pla" {...props}></Icon>
