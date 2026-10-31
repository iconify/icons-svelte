<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9eiabb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9eiabb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h6-solid" {...props}></Icon>
