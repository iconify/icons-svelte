<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4azuyx3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s4azuyx3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pinterest-filled" {...props}></Icon>
