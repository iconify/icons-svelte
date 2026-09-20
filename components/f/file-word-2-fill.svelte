<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywfef-bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywfef-bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-word-2-fill" {...props}></Icon>
