<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqw1kdbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqw1kdbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:carbon-offset" {...props}></Icon>
