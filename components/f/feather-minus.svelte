<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfk79ebkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfk79ebkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:feather-minus" {...props}></Icon>
