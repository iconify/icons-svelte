<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc9z1mbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc9z1mbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bug-alt-filled" {...props}></Icon>
