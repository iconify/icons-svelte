<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w19wmsbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w19wmsbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-share-alt" {...props}></Icon>
