<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcn3ptbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcn3ptbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lamp-charge-filled" {...props}></Icon>
