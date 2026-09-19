<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbqe6cbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hbqe6cbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-square-fill" {...props}></Icon>
