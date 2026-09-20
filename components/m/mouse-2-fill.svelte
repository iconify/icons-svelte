<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td859mbpm.css';
import '../../css/p/pmiyxhb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td859mbpm"/><path class="pmiyxhb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:mouse-2-fill" {...props}></Icon>
