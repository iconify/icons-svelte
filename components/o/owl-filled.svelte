<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeftv-f_s.css';
import '../../css/w/wwi7ougfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeftv-f_s"/><path class="wwi7ougfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:owl-filled" {...props}></Icon>
