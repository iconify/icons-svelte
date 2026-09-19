<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d86adob8w.css';
import '../../css/b/bvt239bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d86adob8w"/><path class="bvt239bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-z" {...props}></Icon>
