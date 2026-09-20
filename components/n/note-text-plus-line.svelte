<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui-vjc08x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui-vjc08x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:note-text-plus-line" {...props}></Icon>
