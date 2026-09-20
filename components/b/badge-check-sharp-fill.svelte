<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyf0sk1kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lyf0sk1kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-check-sharp-fill" {...props}></Icon>
