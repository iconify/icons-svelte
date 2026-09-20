<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/actx8vb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="actx8vb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dcb" {...props}></Icon>
