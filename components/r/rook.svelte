<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-yvlgv8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-yvlgv8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rook" {...props}></Icon>
