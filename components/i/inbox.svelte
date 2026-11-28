<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au8312wop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au8312wop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:inbox" {...props}></Icon>
