<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxrmtyu_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxrmtyu_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:circle-chevron-right-fill" {...props}></Icon>
