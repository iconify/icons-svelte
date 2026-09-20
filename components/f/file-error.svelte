<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw7q3l5ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jw7q3l5ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:file-error" {...props}></Icon>
