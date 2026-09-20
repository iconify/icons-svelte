<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqbzxccjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qqbzxccjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kine" {...props}></Icon>
