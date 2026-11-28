<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmg3osppk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmg3osppk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fridge-alert" {...props}></Icon>
