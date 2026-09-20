<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjqc-qb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjqc-qb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hat-2-fill" {...props}></Icon>
