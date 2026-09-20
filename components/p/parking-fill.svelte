<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta5wkcqyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta5wkcqyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parking-fill" {...props}></Icon>
