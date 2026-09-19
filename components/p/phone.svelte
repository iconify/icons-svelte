<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf2fybc0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf2fybc0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:phone" {...props}></Icon>
