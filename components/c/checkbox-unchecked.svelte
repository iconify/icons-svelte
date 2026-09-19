<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p77veefer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p77veefer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:checkbox-unchecked" {...props}></Icon>
