<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozv103bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozv103bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-heading-decease" {...props}></Icon>
