<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbw7_8o6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbw7_8o6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-down-duotone" {...props}></Icon>
