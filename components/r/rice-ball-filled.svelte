<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhtyav7tz.css';
import '../../css/k/kvketbp9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhtyav7tz"/><path class="kvketbp9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rice-ball-filled" {...props}></Icon>
