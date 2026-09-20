<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1i63cbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1i63cbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:reduce" {...props}></Icon>
