<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed85gr18x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ed85gr18x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:compass-fill" {...props}></Icon>
