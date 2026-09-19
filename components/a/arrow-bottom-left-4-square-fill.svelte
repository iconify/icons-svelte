<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvl_7yb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvl_7yb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-4-square-fill" {...props}></Icon>
