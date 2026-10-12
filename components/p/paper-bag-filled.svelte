<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfl8apr-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfl8apr-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paper-bag-filled" {...props}></Icon>
