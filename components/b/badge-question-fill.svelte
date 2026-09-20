<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muhx-4g7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="muhx-4g7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-question-fill" {...props}></Icon>
