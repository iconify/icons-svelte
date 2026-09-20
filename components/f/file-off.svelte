<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5bt6abqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5bt6abqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-off" {...props}></Icon>
