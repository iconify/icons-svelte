<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l68-xqbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l68-xqbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aiming-2-fill" {...props}></Icon>
