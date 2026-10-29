<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh4rqfpek.css';
import '../../css/r/rzrmuq82c.css';
import '../../css/c/c1uaxoita.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4rqfpek"/><path class="rzrmuq82c"/><path class="c1uaxoita"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:align-right" {...props}></Icon>
