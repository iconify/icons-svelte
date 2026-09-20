<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5nhvabix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y5nhvabix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:checkmark-circle-checked-solid-expressive" {...props}></Icon>
