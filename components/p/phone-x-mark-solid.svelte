<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo4lcqbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xo4lcqbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:phone-x-mark-solid" {...props}></Icon>
