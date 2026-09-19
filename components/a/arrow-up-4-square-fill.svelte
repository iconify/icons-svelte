<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzv55vozr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wzv55vozr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-up-4-square-fill" {...props}></Icon>
