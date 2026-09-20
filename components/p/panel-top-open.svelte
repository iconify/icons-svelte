<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znun6c7ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znun6c7ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-open" {...props}></Icon>
