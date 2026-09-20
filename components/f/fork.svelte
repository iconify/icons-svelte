<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylugz1g1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ylugz1g1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:fork" {...props}></Icon>
