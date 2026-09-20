<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlxb7bcwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qlxb7bcwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:page-break-remix" {...props}></Icon>
