<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lix1ev9xm.css';
import '../../css/j/jjbqhzpum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lix1ev9xm"/><path class="jjbqhzpum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:filter-none-fill" {...props}></Icon>
