<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo8q3jb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo8q3jb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-branch-fill" {...props}></Icon>
