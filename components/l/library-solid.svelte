<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrtf6oooz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrtf6oooz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:library-solid" {...props}></Icon>
