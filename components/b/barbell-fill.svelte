<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjs4o1qnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjs4o1qnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barbell-fill" {...props}></Icon>
