<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqelz6bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqelz6bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-text-info" {...props}></Icon>
