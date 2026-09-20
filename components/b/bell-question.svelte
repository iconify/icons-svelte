<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyq89wxfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyq89wxfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-question" {...props}></Icon>
