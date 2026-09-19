<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu_5mwbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1026};
const content = `<path class="wu_5mwbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lemon" {...props}></Icon>
