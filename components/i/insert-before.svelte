<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgc7y8xwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgc7y8xwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:insert-before" {...props}></Icon>
