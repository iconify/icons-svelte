<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv0b-4b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv0b-4b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:phone-incoming" {...props}></Icon>
