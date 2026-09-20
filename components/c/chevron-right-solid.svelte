<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywoke0pnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywoke0pnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chevron-right-solid" {...props}></Icon>
