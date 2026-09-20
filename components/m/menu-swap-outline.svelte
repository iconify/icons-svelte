<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq_6gjbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq_6gjbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:menu-swap-outline" {...props}></Icon>
