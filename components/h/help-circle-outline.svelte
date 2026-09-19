<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf19r5bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf19r5bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:help-circle-outline" {...props}></Icon>
