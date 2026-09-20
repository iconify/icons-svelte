<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv3lzbckl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv3lzbckl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:note-text" {...props}></Icon>
