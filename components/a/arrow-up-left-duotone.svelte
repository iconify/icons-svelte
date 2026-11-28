<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3q-b4urp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v3q-b4urp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-left-duotone" {...props}></Icon>
