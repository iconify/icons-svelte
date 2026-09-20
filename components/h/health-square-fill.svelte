<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txyd36pzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txyd36pzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:health-square-fill" {...props}></Icon>
