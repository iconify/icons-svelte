<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1a5oq34v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p1a5oq34v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:paper-clock-solid" {...props}></Icon>
