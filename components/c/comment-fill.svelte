<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oji4ukc8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oji4ukc8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment-fill" {...props}></Icon>
