<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9clepwnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9clepwnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:notion-fill-round" {...props}></Icon>
