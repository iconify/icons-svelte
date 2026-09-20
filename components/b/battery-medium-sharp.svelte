<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvu-1h28a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvu-1h28a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:battery-medium-sharp" {...props}></Icon>
