<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm9476rqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rm9476rqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:check-circle-alt-01" {...props}></Icon>
