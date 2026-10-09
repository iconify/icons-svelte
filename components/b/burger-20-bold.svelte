<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7m3rdb3k.css';
import '../../css/s/s9upufoui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z7m3rdb3k"/><path class="s9upufoui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:burger-20-bold" {...props}></Icon>
