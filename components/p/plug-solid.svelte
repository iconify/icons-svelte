<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilitycbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ilitycbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:plug-solid" {...props}></Icon>
