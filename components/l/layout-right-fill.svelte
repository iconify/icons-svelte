<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp4ayr8uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp4ayr8uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:layout-right-fill" {...props}></Icon>
