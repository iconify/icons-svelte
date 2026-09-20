<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzfzdbc4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yzfzdbc4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-setting-bolt-nut-remix" {...props}></Icon>
