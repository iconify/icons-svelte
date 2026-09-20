<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pww4j9bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pww4j9bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:archive-drawer-fill" {...props}></Icon>
