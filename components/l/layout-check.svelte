<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyl65wiih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b zyl65wiih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layout-check" {...props}></Icon>
