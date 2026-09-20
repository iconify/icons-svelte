<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdk94ybiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdk94ybiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:fitbit-logo-bold" {...props}></Icon>
