<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd9xa4bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd9xa4bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:plus-circle" {...props}></Icon>
