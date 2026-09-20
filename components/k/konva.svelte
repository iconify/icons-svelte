<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmm9ihkeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmm9ihkeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:konva" {...props}></Icon>
