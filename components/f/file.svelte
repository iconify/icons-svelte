<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcqvikq6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcqvikq6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file" {...props}></Icon>
