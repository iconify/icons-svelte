<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcu_y75mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qcu_y75mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:medicine-box" {...props}></Icon>
