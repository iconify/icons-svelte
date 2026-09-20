<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgqrdp35g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgqrdp35g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-fill" {...props}></Icon>
