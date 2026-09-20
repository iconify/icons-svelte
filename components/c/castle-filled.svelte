<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz3n_jqgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xz3n_jqgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:castle-filled" {...props}></Icon>
