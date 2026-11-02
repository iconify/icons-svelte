<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b97eqrb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b97eqrb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-right-fill" {...props}></Icon>
