<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blhm5fk1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blhm5fk1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:nurse-fill" {...props}></Icon>
