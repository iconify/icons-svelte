<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkru72b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkru72b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:incognito-bold" {...props}></Icon>
