<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh0-_vmzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh0-_vmzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-type-fill" {...props}></Icon>
