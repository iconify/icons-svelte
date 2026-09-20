<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wez0f6e8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wez0f6e8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-outer-solid" {...props}></Icon>
