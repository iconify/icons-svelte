<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcq6a4frh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcq6a4frh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:caret-down-fill" {...props}></Icon>
