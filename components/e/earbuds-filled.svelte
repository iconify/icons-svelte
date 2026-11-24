<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeyns4pbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeyns4pbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:earbuds-filled" {...props}></Icon>
