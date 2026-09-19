<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya9h86b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ya9h86b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:notification-fill" {...props}></Icon>
