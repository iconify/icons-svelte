<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4wxyjb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4wxyjb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:mobile-phone-fill" {...props}></Icon>
