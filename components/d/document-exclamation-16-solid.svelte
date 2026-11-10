<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0ko-764v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h0ko-764v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:document-exclamation-16-solid" {...props}></Icon>
