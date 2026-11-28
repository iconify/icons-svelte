<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqs_i4b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqs_i4b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:markdown-solid" {...props}></Icon>
