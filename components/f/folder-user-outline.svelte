<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm3zlkn7f.css';
import '../../css/s/sz_qvhbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm3zlkn7f"/><path class="sz_qvhbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-user-outline" {...props}></Icon>
