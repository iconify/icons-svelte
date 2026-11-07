<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiysl7bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yiysl7bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magic-stick-2-outline" {...props}></Icon>
