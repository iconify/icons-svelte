<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzao_8bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzao_8bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-fill" {...props}></Icon>
