<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9n9aw2xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9n9aw2xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-3-fill" {...props}></Icon>
