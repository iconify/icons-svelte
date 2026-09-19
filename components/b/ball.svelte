<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngtu_95cw.css';
import '../../css/f/fqk5odb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngtu_95cw"/><path class="fqk5odb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:ball" {...props}></Icon>
