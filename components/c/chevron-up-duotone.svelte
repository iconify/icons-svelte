<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb_nxg3mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hb_nxg3mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chevron-up-duotone" {...props}></Icon>
