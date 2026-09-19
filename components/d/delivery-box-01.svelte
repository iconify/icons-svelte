<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe1l063ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe1l063ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delivery-box-01" {...props}></Icon>
