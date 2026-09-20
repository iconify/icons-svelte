<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii2j4fp2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii2j4fp2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-music-sharp" {...props}></Icon>
