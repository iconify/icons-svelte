<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cedirc54l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cedirc54l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:notion-solid" {...props}></Icon>
