<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzbtv324v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzbtv324v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-image" {...props}></Icon>
