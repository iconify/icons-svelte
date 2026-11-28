<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcqb7divy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcqb7divy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-zip-check" {...props}></Icon>
