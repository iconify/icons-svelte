<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u79u2pbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u79u2pbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-text-duotone" {...props}></Icon>
