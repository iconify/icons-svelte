<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdzgxo04f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdzgxo04f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-zip-fill" {...props}></Icon>
