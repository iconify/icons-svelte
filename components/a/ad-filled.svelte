<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0-bq5bbi.css';
import '../../css/r/r_ni-0b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0-bq5bbi"/><path clip-rule="evenodd" class="r_ni-0b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ad-filled" {...props}></Icon>
