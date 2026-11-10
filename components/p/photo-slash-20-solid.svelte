<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ada_u3u5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ada_u3u5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:photo-slash-20-solid" {...props}></Icon>
