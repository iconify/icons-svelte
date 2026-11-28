<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frlhmob0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frlhmob0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-open-solid" {...props}></Icon>
