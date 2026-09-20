<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmunasb2f.css';
import '../../css/w/w_bhenb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmunasb2f"/><path class="w_bhenb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:calendar-duotone" {...props}></Icon>
