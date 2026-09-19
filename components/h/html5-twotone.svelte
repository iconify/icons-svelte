<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1pu1rrxi.css';
import '../../css/g/gmc9imcga.css';
import '../../css/y/y192wnsah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j1pu1rrxi"/><path class="gmc9imcga"/><path class="y192wnsah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:html5-twotone" {...props}></Icon>
