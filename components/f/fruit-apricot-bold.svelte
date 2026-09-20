<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixcjz-wtv.css';
import '../../css/u/uhf9ggjia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixcjz-wtv"/><path class="uhf9ggjia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:fruit-apricot-bold" {...props}></Icon>
