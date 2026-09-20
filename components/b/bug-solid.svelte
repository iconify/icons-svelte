<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfm03acay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sfm03acay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:bug-solid" {...props}></Icon>
