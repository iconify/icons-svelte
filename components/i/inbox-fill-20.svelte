<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn3tamb9f.css';
import '../../css/a/a9b7zrdqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vn3tamb9f"/><path class="a9b7zrdqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:inbox-fill-20" {...props}></Icon>
