<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceiehxfky.css';
import '../../css/v/v3pjvgp8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ceiehxfky"/><path class="v3pjvgp8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:form-outlined" {...props}></Icon>
