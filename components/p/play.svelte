<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac0-4ubcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac0-4ubcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:play" {...props}></Icon>
