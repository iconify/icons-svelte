<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh4rqfpek.css';
import '../../css/t/ts-4hsfbk.css';
import '../../css/m/mjnimo6uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4rqfpek"/><path class="ts-4hsfbk"/><path class="mjnimo6uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:align-left" {...props}></Icon>
