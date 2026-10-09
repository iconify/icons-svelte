<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5ui_2cdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s5ui_2cdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-cleaning-20-bold" {...props}></Icon>
