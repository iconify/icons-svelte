<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey9koeo-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey9koeo-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kubespray" {...props}></Icon>
