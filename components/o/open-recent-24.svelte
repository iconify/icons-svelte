<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs6ffwolm.css';
import '../../css/o/oiec-xb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs6ffwolm"/><path clip-rule="evenodd" class="oiec-xb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:open-recent-24" {...props}></Icon>
