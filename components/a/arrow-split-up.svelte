<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tffw4rreh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tffw4rreh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-split-up" {...props}></Icon>
