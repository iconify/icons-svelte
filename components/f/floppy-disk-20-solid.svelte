<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y551u-61r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y551u-61r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:floppy-disk-20-solid" {...props}></Icon>
