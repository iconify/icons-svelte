<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjwem2boo.css';
import '../../css/h/hjgunfmzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jjwem2boo"/><path class="hjgunfmzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:file-upload-outline" {...props}></Icon>
