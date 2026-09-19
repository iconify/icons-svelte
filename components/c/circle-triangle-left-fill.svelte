<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykdahce2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ykdahce2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:circle-triangle-left-fill" {...props}></Icon>
