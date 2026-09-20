<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkh-m2dpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkh-m2dpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:insurance-hands-remix" {...props}></Icon>
