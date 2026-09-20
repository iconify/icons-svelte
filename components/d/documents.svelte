<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/momz31b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="momz31b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:documents" {...props}></Icon>
