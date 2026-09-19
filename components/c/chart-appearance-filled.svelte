<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duzeihb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="duzeihb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-appearance-filled" {...props}></Icon>
