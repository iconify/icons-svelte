<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv2h5uisl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv2h5uisl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:leaf" {...props}></Icon>
