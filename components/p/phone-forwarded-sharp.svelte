<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvw0wvilq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvw0wvilq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:phone-forwarded-sharp" {...props}></Icon>
