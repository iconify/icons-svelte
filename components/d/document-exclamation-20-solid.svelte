<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5yuehbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="o5yuehbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:document-exclamation-20-solid" {...props}></Icon>
