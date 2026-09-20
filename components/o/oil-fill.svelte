<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l87bt4btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l87bt4btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:oil-fill" {...props}></Icon>
