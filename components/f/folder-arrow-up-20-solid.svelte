<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhm-r8bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hhm-r8bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-arrow-up-20-solid" {...props}></Icon>
