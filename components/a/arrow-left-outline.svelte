<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd798bcah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd798bcah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:arrow-left-outline" {...props}></Icon>
