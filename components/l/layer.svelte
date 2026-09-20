<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smphz81xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smphz81xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:layer" {...props}></Icon>
