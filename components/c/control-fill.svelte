<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd014-png.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nd014-png"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:control-fill" {...props}></Icon>
