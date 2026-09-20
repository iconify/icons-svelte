<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eloyzw0ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eloyzw0ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gusd" {...props}></Icon>
