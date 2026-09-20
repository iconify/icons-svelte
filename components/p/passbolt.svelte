<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnepxqa4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnepxqa4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:passbolt" {...props}></Icon>
