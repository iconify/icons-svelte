<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_no1bbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_no1bbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:phone-off-fill" {...props}></Icon>
