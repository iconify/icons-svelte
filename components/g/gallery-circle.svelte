<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0fq5ib_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0fq5ib_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gallery-circle" {...props}></Icon>
