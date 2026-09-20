<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljkibzbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljkibzbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:battery-empty" {...props}></Icon>
