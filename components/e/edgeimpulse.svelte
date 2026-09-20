<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utf5gactz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utf5gactz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:edgeimpulse" {...props}></Icon>
