<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6d6djalc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6d6djalc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hand-sparkles-solid" {...props}></Icon>
