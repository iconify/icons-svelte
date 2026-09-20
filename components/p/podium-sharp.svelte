<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr4a1nbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr4a1nbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:podium-sharp" {...props}></Icon>
