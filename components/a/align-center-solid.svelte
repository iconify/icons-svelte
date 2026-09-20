<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h49p6u_wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h49p6u_wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:align-center-solid" {...props}></Icon>
