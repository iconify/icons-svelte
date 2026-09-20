<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckioaocrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckioaocrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:rhombus" {...props}></Icon>
