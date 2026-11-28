<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_52p3bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_52p3bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-left-square-solid" {...props}></Icon>
