<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-ggtpb7h.css';
import '../../css/o/ojum2hmgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-ggtpb7h"/><path class="ojum2hmgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:church-filled" {...props}></Icon>
