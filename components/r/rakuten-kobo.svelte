<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spfb5kbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spfb5kbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rakuten-kobo" {...props}></Icon>
