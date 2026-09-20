<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf3hkbb1h.css';
import '../../css/u/u8acicc4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf3hkbb1h"/><path clip-rule="evenodd" class="u8acicc4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:menu-dots-circle-24" {...props}></Icon>
