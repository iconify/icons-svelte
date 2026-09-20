<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-yut1b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-yut1b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:asterisk-simple" {...props}></Icon>
