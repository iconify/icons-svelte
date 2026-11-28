<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sozw1eb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sozw1eb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:navigation-solid" {...props}></Icon>
