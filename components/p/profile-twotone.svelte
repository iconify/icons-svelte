<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc8-4tb2b.css';
import '../../css/u/ufrvvubmu.css';
import '../../css/z/zy-6bbbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="ufrvvubmu"/><path class="zy-6bbbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:profile-twotone" {...props}></Icon>
