<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogx8amvsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ogx8amvsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:attention-circle-fill" {...props}></Icon>
