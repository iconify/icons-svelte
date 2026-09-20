<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f93xtsbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f93xtsbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:caret-left-fill" {...props}></Icon>
