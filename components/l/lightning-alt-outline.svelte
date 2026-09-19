<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnn96f57y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qnn96f57y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:lightning-alt-outline" {...props}></Icon>
