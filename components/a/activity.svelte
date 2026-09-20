<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv7_uiesw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv7_uiesw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:activity" {...props}></Icon>
