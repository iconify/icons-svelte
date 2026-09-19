<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3mpyzbst.css';
import '../../css/k/ka0ihjbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3mpyzbst"/><path class="ka0ihjbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-png" {...props}></Icon>
