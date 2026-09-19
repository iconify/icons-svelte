<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thcw70a2b.css';
import '../../css/v/vawhvpbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thcw70a2b"/><path clip-rule="evenodd" class="vawhvpbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-block-solid" {...props}></Icon>
