<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fim5e0ajp.css';
import '../../css/a/asnejb9av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fim5e0ajp"/><path class="asnejb9av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-wechat-20" {...props}></Icon>
