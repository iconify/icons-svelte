<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj59mebze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zj59mebze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:credit-card-2-remix" {...props}></Icon>
