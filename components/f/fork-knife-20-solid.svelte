<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzgij3q9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wzgij3q9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:fork-knife-20-solid" {...props}></Icon>
