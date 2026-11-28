<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4kyqmk7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4kyqmk7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-open-x" {...props}></Icon>
