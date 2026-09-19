<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm6l8ktey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qm6l8ktey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:calculator-outline" {...props}></Icon>
