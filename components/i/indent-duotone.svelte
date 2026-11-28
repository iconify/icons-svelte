<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flgb0ccza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flgb0ccza primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:indent-duotone" {...props}></Icon>
