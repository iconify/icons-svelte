<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja_yhub6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ja_yhub6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-dlig-small-filled" {...props}></Icon>
