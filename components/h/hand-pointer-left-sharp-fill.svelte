<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxgweyz7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yxgweyz7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-pointer-left-sharp-fill" {...props}></Icon>
