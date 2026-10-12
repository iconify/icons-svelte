<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa_--1afw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa_--1afw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-chevron-left-filled" {...props}></Icon>
