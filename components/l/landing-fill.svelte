<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd4-2ibfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd4-2ibfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:landing-fill" {...props}></Icon>
