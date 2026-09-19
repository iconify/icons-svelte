<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwkbxxb3f.css';
import '../../css/f/fkq9d_i7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwkbxxb3f"/><path class="fkq9d_i7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:history" {...props}></Icon>
