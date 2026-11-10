<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abfudubwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="abfudubwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-arrow-path-16-solid" {...props}></Icon>
