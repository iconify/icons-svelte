<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyg5p4b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nyg5p4b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:crown-20-solid" {...props}></Icon>
