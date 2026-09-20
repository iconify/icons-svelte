<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woeg8eetv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woeg8eetv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:coin-a-fill" {...props}></Icon>
