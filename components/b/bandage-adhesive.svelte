<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-js8ibul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f-js8ibul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bandage-adhesive" {...props}></Icon>
