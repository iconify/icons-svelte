<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag36mlbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag36mlbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:battery-full" {...props}></Icon>
