<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niwqy6-id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niwqy6-id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:color-swatch-filled" {...props}></Icon>
