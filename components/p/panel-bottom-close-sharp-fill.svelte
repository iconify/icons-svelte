<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjm4x02vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjm4x02vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-close-sharp-fill" {...props}></Icon>
