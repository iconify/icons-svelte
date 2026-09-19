<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puqv5u2-o.css';
import '../../css/n/ngen2gb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puqv5u2-o"/><path class="ngen2gb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-duplicate" {...props}></Icon>
