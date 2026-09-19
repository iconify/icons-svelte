<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn4hukbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn4hukbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:earbuds-filled" {...props}></Icon>
