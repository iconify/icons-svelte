<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el-kvbb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el-kvbb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hyve" {...props}></Icon>
