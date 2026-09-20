<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv0z9ub6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv0z9ub6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:open-source" {...props}></Icon>
