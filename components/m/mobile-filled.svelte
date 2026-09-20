<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4-vlhb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e4-vlhb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mobile-filled" {...props}></Icon>
