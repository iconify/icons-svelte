<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui6rey9mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui6rey9mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mark-pen-line" {...props}></Icon>
