<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zml4mvy9b.css';
import '../../css/g/gertnpb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zml4mvy9b"/><path class="gertnpb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:arrow-down" {...props}></Icon>
