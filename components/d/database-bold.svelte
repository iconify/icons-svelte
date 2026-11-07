<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky6edpbsi.css';
import '../../css/i/i6kkc5sfl.css';
import '../../css/w/wcscpib-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky6edpbsi"/><path class="i6kkc5sfl"/><path class="wcscpib-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:database-bold" {...props}></Icon>
