<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyd6mobsh.css';
import '../../css/s/sv7nt6skj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyd6mobsh"/><path class="sv7nt6skj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:export" {...props}></Icon>
