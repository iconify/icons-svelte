<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj3tasbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj3tasbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-connect" {...props}></Icon>
