<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dguhqwg8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dguhqwg8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:react-fill" {...props}></Icon>
