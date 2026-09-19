<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bizf7qbor.css';
import '../../css/h/heochxbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bizf7qbor"/><path clip-rule="evenodd" class="heochxbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:arrow-down-outline" {...props}></Icon>
