<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwf8dez8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwf8dez8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-3-light" {...props}></Icon>
