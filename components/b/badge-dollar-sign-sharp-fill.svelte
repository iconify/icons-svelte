<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejli6su1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ejli6su1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-dollar-sign-sharp-fill" {...props}></Icon>
