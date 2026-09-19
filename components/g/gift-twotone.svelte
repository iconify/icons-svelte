<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np8ilvg5i.css';
import '../../css/s/s9zx-k-iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="np8ilvg5i"/><path class="s9zx-k-iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:gift-twotone" {...props}></Icon>
