<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq5--8b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zq5--8b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chevron-down-solid" {...props}></Icon>
