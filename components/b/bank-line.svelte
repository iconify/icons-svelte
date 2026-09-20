<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxoqcdtnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxoqcdtnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bank-line" {...props}></Icon>
