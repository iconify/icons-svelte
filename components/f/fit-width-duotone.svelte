<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwl57ubde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary xwl57ubde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fit-width-duotone" {...props}></Icon>
