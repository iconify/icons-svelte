<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcmq74bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcmq74bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:link-slash" {...props}></Icon>
