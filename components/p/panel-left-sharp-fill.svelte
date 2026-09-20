<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0iw1wi4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0iw1wi4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-left-sharp-fill" {...props}></Icon>
