<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjrb-gbdh.css';
import '../../css/r/rkdm0ob1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gjrb-gbdh"/><path class="rkdm0ob1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-products-boat-success" {...props}></Icon>
