<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydc7yznbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydc7yznbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:phone-outgoing-sharp" {...props}></Icon>
