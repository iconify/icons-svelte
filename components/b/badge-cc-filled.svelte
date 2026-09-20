<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk7uk6brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk7uk6brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-cc-filled" {...props}></Icon>
