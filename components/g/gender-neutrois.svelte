<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fugyre1oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fugyre1oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gender-neutrois" {...props}></Icon>
