<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbo0hyrvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbo0hyrvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:indent" {...props}></Icon>
