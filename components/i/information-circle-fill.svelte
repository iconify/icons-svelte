<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhmidqb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hhmidqb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:information-circle-fill" {...props}></Icon>
