<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/safc_lb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5.5};
const content = `<path class="safc_lb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:behance" {...props}></Icon>
