<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax9gbu_0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ax9gbu_0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:mastodon-filled" {...props}></Icon>
