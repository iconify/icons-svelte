<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm_0jcbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm_0jcbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bank-fill-round" {...props}></Icon>
