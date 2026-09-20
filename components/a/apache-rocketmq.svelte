<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8pmyt8ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8pmyt8ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-rocketmq" {...props}></Icon>
