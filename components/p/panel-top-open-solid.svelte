<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhkdmcvso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhkdmcvso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-top-open-solid" {...props}></Icon>
