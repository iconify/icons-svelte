<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3se7-35b.css';
import '../../css/d/dkh-5rbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3se7-35b"/><path class="dkh-5rbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cloud-rain" {...props}></Icon>
