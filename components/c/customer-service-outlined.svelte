<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9r3_1dmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z9r3_1dmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:customer-service-outlined" {...props}></Icon>
