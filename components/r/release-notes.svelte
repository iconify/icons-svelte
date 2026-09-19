<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bydntfeiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bydntfeiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:release-notes" {...props}></Icon>
