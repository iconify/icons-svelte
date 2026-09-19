<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pydz04b8f.css';
import '../../css/o/ockmixada.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pydz04b8f"/><path class="ockmixada"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:basket" {...props}></Icon>
