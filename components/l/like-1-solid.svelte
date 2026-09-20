<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa_hafb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qa_hafb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:like-1-solid" {...props}></Icon>
