<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlw7c8bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlw7c8bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:grid" {...props}></Icon>
