<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j02vs_14r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j02vs_14r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:flag-alt" {...props}></Icon>
