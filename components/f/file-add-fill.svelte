<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo7wm5voy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zo7wm5voy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-add-fill" {...props}></Icon>
