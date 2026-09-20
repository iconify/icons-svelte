<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1x3wj3gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b1x3wj3gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-line-fill" {...props}></Icon>
