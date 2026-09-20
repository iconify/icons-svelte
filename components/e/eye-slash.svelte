<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq6n_s_po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kq6n_s_po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:eye-slash" {...props}></Icon>
