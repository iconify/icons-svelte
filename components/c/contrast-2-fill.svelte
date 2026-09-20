<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4c-gkjcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4c-gkjcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contrast-2-fill" {...props}></Icon>
