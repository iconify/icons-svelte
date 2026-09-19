<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afafpebrx.css';
import '../../css/s/sv58jibeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afafpebrx"/><path class="sv58jibeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:doughnut-chart-filled" {...props}></Icon>
