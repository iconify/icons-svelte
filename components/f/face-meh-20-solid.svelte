<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeo5cvbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="aeo5cvbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-meh-20-solid" {...props}></Icon>
