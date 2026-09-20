<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is0rpl3ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is0rpl3ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hermes" {...props}></Icon>
