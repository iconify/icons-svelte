<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hooo6gbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hooo6gbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:property-safety-outlined" {...props}></Icon>
