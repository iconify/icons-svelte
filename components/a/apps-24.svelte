<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm2t-hb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm2t-hb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:apps-24" {...props}></Icon>
