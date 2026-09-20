<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egf1rkb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egf1rkb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googledrive" {...props}></Icon>
