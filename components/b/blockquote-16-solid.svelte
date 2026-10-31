<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2rnrdb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i2rnrdb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:blockquote-16-solid" {...props}></Icon>
