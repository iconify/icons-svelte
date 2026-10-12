<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbg283bvc.css';
import '../../css/z/z8ho9sb_d.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbg283bvc"/><path clip-rule="evenodd" class="z8ho9sb_d"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-search-corner-filled" {...props}></Icon>
