<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynj2_0btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynj2_0btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:down" {...props}></Icon>
