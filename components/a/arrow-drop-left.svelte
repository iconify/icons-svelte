<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa6d_acfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa6d_acfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-drop-left" {...props}></Icon>
