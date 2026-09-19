<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bramihlnm.css';
import '../../css/w/wpxuws29w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bramihlnm"/><path class="wpxuws29w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:edit-twotone" {...props}></Icon>
