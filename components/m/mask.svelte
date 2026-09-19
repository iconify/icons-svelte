<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itcbl5dki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itcbl5dki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:mask" {...props}></Icon>
