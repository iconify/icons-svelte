<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-9-h2b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-9-h2b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:empty-slot-24" {...props}></Icon>
