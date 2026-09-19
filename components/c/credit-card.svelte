<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijc_7ccrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ijc_7ccrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:credit-card" {...props}></Icon>
