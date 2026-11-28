<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_7r6jbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_7r6jbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-sparkles-solid" {...props}></Icon>
